<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw5t0sbxt.css';
import '../../css/u/u2hgkfb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zw5t0sbxt"/><path class="u2hgkfb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-price-48-bold" /></template>
