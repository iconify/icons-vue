<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz1_chbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz1_chbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:codepen" /></template>
