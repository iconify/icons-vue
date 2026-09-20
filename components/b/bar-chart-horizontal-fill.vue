<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doficdwjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doficdwjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bar-chart-horizontal-fill" /></template>
