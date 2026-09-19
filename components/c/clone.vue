<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3jp_r57s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="w3jp_r57s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:clone" /></template>
