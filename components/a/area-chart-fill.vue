<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpgehrbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpgehrbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:area-chart-fill" /></template>
