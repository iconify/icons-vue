<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-g_e9_nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-g_e9_nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:coins" /></template>
