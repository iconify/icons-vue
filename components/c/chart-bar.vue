<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8x1c9bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k8x1c9bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:chart-bar" /></template>
