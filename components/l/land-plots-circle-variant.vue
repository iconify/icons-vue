<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxhmt_b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxhmt_b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:land-plots-circle-variant" /></template>
