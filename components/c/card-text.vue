<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5al98e6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5al98e6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:card-text" /></template>
