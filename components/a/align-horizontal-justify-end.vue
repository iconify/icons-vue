<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cez3dxbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cez3dxbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-justify-end" /></template>
