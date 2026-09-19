<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m34qxgbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="m34qxgbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrows-expand-duo" /></template>
