<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qowogqocs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qowogqocs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-reload-horizontal-2-flat" /></template>
