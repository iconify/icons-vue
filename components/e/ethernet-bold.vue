<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfjt46bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mfjt46bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:ethernet-bold" /></template>
