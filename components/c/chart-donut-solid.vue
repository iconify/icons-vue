<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u39vt1b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u39vt1b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-donut-solid" /></template>
