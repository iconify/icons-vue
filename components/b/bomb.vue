<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x85cs3buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x85cs3buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bomb" /></template>
