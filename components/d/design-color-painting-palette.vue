<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_vyfibua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h_vyfibua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-color-painting-palette" /></template>
