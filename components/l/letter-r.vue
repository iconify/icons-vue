<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh62xlrrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh62xlrrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-r" /></template>
