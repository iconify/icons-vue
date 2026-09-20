<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggbltf6qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggbltf6qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:landslide" /></template>
