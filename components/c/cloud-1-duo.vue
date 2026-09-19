<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktdy_3blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ktdy_3blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cloud-1-duo" /></template>
