<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xey7e3bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xey7e3bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:loading-compact" /></template>
