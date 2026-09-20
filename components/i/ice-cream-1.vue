<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0uk58atx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0uk58atx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ice-cream-1" /></template>
