<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka3ubxb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ka3ubxb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:letter-spacing-bold" /></template>
