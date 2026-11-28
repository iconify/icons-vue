<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufpt_wb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ufpt_wb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:helicopter-bold" /></template>
