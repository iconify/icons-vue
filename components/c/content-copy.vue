<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izc259z0t.css';
import '../../css/u/u29y0z2tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="izc259z0t"/><path class="u29y0z2tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-copy" /></template>
