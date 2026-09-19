<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv-tlrbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv-tlrbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:bar-chart-fill" /></template>
