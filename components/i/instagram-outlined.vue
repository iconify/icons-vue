<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig3-qac5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ig3-qac5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:instagram-outlined" /></template>
