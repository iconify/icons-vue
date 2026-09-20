<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwhlbhpyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwhlbhpyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:folder" /></template>
