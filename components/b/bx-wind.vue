<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6eyopbhz.css';
import '../../css/d/dxpxq77kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6eyopbhz"/><path class="dxpxq77kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-wind" /></template>
