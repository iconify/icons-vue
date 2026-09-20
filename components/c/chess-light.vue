<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m25d_fb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m25d_fb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:chess-light" /></template>
