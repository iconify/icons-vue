<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6a8c-fpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":216.75,"height":91.5};
const content = `<path class="g6a8c-fpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flowise" /></template>
