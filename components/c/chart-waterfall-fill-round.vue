<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfcsc6zzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfcsc6zzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-waterfall-fill-round" /></template>
