<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chwev6blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chwev6blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cupboard-outline" /></template>
