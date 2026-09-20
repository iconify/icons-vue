<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa25-xbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa25-xbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:coffee" /></template>
