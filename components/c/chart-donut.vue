<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q67avmb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="q67avmb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:chart-donut" /></template>
