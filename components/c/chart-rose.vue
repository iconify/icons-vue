<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-7nv8f5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l-7nv8f5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-rose" /></template>
