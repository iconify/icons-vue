<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cftlv9b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cftlv9b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line-duotone-round" /></template>
