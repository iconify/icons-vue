<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trt6jobuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="trt6jobuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:laptop-one" /></template>
