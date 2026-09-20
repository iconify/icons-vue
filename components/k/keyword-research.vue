<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5z5kabyv.css';
import '../../css/k/kd452xpng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o5z5kabyv"/><path class="kd452xpng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:keyword-research" /></template>
