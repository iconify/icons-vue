<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usaq-2ubc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usaq-2ubc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:lollipop" /></template>
