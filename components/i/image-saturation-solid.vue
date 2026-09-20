<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgisir4yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fgisir4yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:image-saturation-solid" /></template>
