<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq1w66ubm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq1w66ubm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-panel-top" /></template>
