<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skm4p0brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skm4p0brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-pie-chart-alt" /></template>
