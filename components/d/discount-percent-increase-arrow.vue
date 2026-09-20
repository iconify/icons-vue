<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1cp0nbej.css';
import '../../css/e/em0p01pxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1cp0nbej"/><path class="em0p01pxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:discount-percent-increase-arrow" /></template>
