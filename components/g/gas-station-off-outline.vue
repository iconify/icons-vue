<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc67x7txf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc67x7txf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gas-station-off-outline" /></template>
