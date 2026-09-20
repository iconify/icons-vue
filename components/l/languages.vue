<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xys4lib4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xys4lib4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:languages" /></template>
