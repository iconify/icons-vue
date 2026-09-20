<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrslkfcjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="nrslkfcjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:baseball" /></template>
