<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idga7wb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="idga7wb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gas-station-eco" /></template>
