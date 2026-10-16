<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf5g0ffhl.css';
import '../../css/h/huv6-s8fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cf5g0ffhl"/><path class="huv6-s8fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-detector-20" /></template>
