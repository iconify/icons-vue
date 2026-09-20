<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atmwxtv7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atmwxtv7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:hourglass-glyph" /></template>
