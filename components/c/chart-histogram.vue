<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dan00jbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dan00jbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-histogram" /></template>
