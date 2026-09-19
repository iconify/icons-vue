<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bljlf24ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bljlf24ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-sass" /></template>
