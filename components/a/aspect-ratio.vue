<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-w_9x0ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r-w_9x0ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:aspect-ratio" /></template>
