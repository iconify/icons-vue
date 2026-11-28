<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sas_macef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sas_macef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cassette-play" /></template>
