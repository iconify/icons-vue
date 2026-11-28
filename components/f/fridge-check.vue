<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh92gt4eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh92gt4eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:fridge-check" /></template>
