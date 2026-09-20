<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf_0yyubz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf_0yyubz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-croissant" /></template>
