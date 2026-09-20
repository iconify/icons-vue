<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfne-sg-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfne-sg-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bar-chart-horizontal-line" /></template>
