<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc2qibbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xc2qibbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-4" /></template>
