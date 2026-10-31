<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5_5al_xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5_5al_xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-down-right-fill-round" /></template>
