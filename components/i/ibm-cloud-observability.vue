<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu8zeqbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uu8zeqbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-observability" /></template>
