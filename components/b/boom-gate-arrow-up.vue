<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhtdthmab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhtdthmab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:boom-gate-arrow-up" /></template>
