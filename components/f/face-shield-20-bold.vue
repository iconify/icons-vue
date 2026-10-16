<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ske3-m5ph.css';
import '../../css/s/scl-k_bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ske3-m5ph"/><path class="scl-k_bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:face-shield-20-bold" /></template>
