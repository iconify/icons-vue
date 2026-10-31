<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6knm2bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6knm2bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-minus-corner-round" /></template>
