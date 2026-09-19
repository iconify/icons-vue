<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxg8f6bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cxg8f6bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eraser-stroke-12" /></template>
