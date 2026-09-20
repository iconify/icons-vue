<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x01th1b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x01th1b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-2-horizontal-end-fill" /></template>
