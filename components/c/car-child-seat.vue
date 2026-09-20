<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ldm2_wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ldm2_wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-child-seat" /></template>
