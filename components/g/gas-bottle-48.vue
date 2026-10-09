<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oitekc77l.css';
import '../../css/m/m6f9qoawr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oitekc77l"/><path class="m6f9qoawr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-bottle-48" /></template>
