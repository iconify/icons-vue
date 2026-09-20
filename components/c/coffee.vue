<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp6bw1b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zp6bw1b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:coffee" /></template>
