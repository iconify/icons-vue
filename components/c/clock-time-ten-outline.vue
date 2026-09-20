<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtg7zvgcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtg7zvgcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-ten-outline" /></template>
