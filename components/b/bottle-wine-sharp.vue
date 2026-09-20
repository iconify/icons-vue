<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uimau6ftx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uimau6ftx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bottle-wine-sharp" /></template>
