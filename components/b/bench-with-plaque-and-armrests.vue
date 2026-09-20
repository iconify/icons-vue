<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf6dfce5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kf6dfce5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bench-with-plaque-and-armrests" /></template>
