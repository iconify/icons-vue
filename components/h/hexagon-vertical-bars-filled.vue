<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0s23acch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s0s23acch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:hexagon-vertical-bars-filled" /></template>
