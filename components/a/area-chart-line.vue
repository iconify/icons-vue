<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj0h3714z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj0h3714z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:area-chart-line" /></template>
