<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erzf03bmv.css';
import '../../css/k/kd8y0_bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/><path class="kd8y0_bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:gl-1x1" /></template>
