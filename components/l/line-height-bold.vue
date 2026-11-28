<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvuzmly5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kvuzmly5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:line-height-bold" /></template>
