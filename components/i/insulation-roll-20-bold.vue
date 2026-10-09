<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2do86btb.css';
import '../../css/w/wh481vbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i2do86btb"/><path class="wh481vbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:insulation-roll-20-bold" /></template>
