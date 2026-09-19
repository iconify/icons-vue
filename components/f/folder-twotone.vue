<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s310mjyrf.css';
import '../../css/p/pvkzb2byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s310mjyrf"/><path class="pvkzb2byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:folder-twotone" /></template>
