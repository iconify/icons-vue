<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5yi3v23j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c5yi3v23j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:gitlab" /></template>
