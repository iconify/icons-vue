<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r06aysbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r06aysbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:drop-area" /></template>
