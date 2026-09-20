<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trt_o2bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="trt_o2bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:compass-square-outline" /></template>
