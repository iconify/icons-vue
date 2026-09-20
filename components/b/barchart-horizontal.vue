<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8kir_j1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="c8kir_j1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:barchart-horizontal" /></template>
