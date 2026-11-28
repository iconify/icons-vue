<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwsqh5lqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwsqh5lqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:highlighter" /></template>
