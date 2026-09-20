<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0y22ccdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0y22ccdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:filter" /></template>
