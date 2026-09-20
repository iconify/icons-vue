<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_dt9zbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_dt9zbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chart-bar-big" /></template>
