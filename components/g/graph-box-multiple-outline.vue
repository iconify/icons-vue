<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suireybjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suireybjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:graph-box-multiple-outline" /></template>
