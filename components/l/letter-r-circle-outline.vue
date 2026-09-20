<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo-lowbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo-lowbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-r-circle-outline" /></template>
