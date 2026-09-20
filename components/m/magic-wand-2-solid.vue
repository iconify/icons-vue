<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuksv_b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vuksv_b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:magic-wand-2-solid" /></template>
