<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve7vcj02a.css';
import '../../css/o/okcnfabkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve7vcj02a"/><path class="okcnfabkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-line-chart-down" /></template>
