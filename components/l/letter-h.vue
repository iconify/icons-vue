<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfxsk6b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfxsk6b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-h" /></template>
