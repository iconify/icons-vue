<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i98g5tvxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i98g5tvxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:license-plate-bold" /></template>
