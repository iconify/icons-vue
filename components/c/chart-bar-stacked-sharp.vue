<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml2y4kw_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml2y4kw_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bar-stacked-sharp" /></template>
