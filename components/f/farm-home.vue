<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xphyfpx8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xphyfpx8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:farm-home" /></template>
