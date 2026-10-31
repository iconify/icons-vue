<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rttglkhyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rttglkhyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-funnel-gloss" /></template>
