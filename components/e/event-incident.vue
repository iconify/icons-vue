<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-2wu0c7s.css';
import '../../css/k/ksujj2ycj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y-2wu0c7s"/><path class="ksujj2ycj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:event-incident" /></template>
