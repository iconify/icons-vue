<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwd5ignwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwd5ignwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:input-check" /></template>
