<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfwm_-4ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sfwm_-4ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:eraser" /></template>
