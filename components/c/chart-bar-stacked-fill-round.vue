<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re44xpbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re44xpbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-stacked-fill-round" /></template>
