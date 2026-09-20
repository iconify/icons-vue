<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r201o_bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r201o_bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:city-gate-14" /></template>
