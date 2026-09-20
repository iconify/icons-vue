<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epqu04bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epqu04bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:crop-rotate" /></template>
