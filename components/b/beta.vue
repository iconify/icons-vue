<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh9_36b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wh9_36b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:beta" /></template>
