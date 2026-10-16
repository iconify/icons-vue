<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yotzztbdp.css';
import '../../css/r/rwd6-lkjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yotzztbdp"/><path class="rwd6-lkjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dew-48-bold" /></template>
