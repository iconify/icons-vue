<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u86v46blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u86v46blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cellular-network-lte" /></template>
