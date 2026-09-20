<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7_h__bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e7_h__bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bar-chart" /></template>
