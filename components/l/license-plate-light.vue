<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8czn4ppr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="n8czn4ppr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:license-plate-light" /></template>
