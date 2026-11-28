<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rszk1ccdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rszk1ccdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:fish" /></template>
