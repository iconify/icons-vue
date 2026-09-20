<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcc4ktbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcc4ktbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:left-arrow" /></template>
