<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvgql0brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvgql0brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-spline-fill" /></template>
