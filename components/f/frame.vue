<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooi9z9bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ooi9z9bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:frame" /></template>
