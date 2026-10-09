<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9f9bgb4v.css';
import '../../css/r/rtxnsrb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9f9bgb4v"/><path class="rtxnsrb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-efficiency-48" /></template>
