<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcqpgct8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hcqpgct8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bar-chart-fill-16" /></template>
