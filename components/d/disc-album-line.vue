<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvzqwhbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvzqwhbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disc-album-line" /></template>
