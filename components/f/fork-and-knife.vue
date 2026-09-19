<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvgxf_gxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kvgxf_gxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:fork-and-knife" /></template>
