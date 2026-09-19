<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmpf0vbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmpf0vbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-happy-heart-eyes" /></template>
