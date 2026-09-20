<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4ivq3blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4ivq3blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:adafruit" /></template>
