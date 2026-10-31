<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbf-hnbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbf-hnbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-area-fill-round" /></template>
