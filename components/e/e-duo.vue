<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyl55v84k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="zyl55v84k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:e-duo" /></template>
