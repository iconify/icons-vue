<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dezwopb-j.css';
import '../../css/y/yzrzqb0op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="yzrzqb0op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-check-48" /></template>
