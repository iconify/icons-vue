<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwulq_bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwulq_bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:looks-two" /></template>
