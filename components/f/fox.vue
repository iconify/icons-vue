<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnlz8vwcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dnlz8vwcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:fox" /></template>
