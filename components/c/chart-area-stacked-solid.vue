<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upp0l4w6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upp0l4w6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-area-stacked-solid" /></template>
