<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccop-1btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ccop-1btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:line-height" /></template>
