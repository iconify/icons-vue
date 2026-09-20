<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9wbj-b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9wbj-b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cross-glyph" /></template>
