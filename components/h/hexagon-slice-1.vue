<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ema37gbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ema37gbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hexagon-slice-1" /></template>
