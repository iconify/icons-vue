<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv5n45bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fv5n45bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:high-speed-train-front-solid" /></template>
