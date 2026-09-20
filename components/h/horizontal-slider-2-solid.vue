<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atxq1m6er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="atxq1m6er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:horizontal-slider-2-solid" /></template>
