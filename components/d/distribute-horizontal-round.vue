<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvr8x-hfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvr8x-hfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-horizontal-round" /></template>
