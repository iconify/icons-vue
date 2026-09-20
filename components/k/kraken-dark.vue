<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij5gh3byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<path class="ij5gh3byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kraken-dark" /></template>
