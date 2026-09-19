<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i07ac8bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i07ac8bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grid-2x2-stroke-16" /></template>
