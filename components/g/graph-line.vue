<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl118cxej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl118cxej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:graph-line" /></template>
