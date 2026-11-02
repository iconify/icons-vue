<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev_cvrjhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev_cvrjhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-2-line" /></template>
