<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaapxab6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaapxab6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:line-chart-up" /></template>
