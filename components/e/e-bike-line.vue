<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s84_ybbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s84_ybbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:e-bike-line" /></template>
