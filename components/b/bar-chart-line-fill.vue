<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imo-0w39a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="imo-0w39a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bar-chart-line-fill" /></template>
