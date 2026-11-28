<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wly1u2umf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wly1u2umf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fridge-check" /></template>
