<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkt0p6bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkt0p6bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gauge-check" /></template>
