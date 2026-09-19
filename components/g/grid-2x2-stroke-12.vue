<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0uoc3w9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y0uoc3w9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grid-2x2-stroke-12" /></template>
