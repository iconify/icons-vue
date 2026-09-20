<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg624rbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg624rbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:frown" /></template>
