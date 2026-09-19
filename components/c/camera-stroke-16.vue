<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud1m1c5-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ud1m1c5-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:camera-stroke-16" /></template>
