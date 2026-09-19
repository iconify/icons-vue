<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyhw9eb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyhw9eb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bar-chart-horizontal" /></template>
