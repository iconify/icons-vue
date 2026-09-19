<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh9-u_epy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oh9-u_epy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-textcolor" /></template>
