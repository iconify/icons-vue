<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxi3_5bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kxi3_5bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bow-and-arrow-thin" /></template>
