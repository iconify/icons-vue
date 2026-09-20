<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgel0ubwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgel0ubwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fog-filled" /></template>
