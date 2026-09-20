<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg_qdjbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg_qdjbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplane-location" /></template>
