<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waq4msb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="waq4msb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-breakpoint-log" /></template>
