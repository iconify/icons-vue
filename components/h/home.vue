<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfib3vzts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfib3vzts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:home" /></template>
