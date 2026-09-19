<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aceok0kpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="aceok0kpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-1-duo" /></template>
