<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9x01chdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9x01chdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-center" /></template>
