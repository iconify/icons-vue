<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxifirbbl.css';
import '../../css/r/ryxm1nv_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxifirbbl"/><path class="ryxm1nv_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:e-commerce-touch-buy-bold" /></template>
