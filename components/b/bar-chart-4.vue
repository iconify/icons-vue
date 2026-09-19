<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp8r7mhcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yp8r7mhcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:bar-chart-4" /></template>
