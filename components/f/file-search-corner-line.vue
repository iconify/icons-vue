<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr8ocvcld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr8ocvcld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-search-corner-line" /></template>
