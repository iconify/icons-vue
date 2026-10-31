<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki9lj6b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki9lj6b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-treemap-round" /></template>
