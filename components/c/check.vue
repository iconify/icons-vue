<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu5teoz6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tu5teoz6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:check" /></template>
