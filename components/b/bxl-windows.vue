<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7hv-mbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7hv-mbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-windows" /></template>
