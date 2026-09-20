<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2lo1actl.css';
import '../../css/u/utw1vrodv.css';
import '../../css/y/y016e8ire.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d2lo1actl"/><path class="utw1vrodv"/><path class="y016e8ire"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-drug-medicine-water" /></template>
