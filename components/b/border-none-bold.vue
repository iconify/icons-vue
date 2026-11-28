<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2fmwm2av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w2fmwm2av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-none-bold" /></template>
