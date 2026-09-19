<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opqkb-jvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opqkb-jvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-css3" /></template>
