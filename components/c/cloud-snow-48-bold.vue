<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-trq2_bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k-trq2_bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-snow-48-bold" /></template>
