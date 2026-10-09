<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvr1cwbqh.css';
import '../../css/q/qfa9e5rcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvr1cwbqh"/><path class="qfa9e5rcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alert-48-bold" /></template>
