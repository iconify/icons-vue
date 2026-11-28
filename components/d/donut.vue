<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flx43mdno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flx43mdno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:donut" /></template>
