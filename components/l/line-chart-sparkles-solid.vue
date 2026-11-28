<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8_x0i1lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8_x0i1lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:line-chart-sparkles-solid" /></template>
