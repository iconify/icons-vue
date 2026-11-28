<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vijc33lrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vijc33lrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:camera-search" /></template>
