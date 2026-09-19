<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8b32nb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="k8b32nb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-trend-down" /></template>
