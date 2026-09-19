<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7t0_yp1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l7t0_yp1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:anchor" /></template>
