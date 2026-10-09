<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yajgwt04s.css';
import '../../css/t/t0m57ubqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yajgwt04s"/><path class="t0m57ubqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-line-20" /></template>
