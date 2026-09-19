<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh4g1sb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="zh4g1sb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cross" /></template>
