<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbb7ehn3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gbb7ehn3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flood" /></template>
