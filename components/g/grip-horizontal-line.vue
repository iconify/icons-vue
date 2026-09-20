<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvx3s30_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvx3s30_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:grip-horizontal-line" /></template>
