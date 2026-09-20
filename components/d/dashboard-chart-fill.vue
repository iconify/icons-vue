<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoi-wib1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoi-wib1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-chart-fill" /></template>
