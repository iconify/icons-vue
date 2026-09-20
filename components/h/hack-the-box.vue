<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm59pb2yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":791.27};
const content = `<path class="rm59pb2yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hack-the-box" /></template>
