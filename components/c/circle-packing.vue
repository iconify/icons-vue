<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6-affb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u6-affb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:circle-packing" /></template>
