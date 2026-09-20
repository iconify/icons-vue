<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvl__wbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvl__wbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:laptop" /></template>
