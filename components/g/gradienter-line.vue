<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv4va0_8o.css';
import '../../css/n/nl5ridb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4va0_8o"/><path class="nl5ridb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gradienter-line" /></template>
