<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htek8vqjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htek8vqjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:joystick-button" /></template>
