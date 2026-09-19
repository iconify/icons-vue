<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jew4uiv9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jew4uiv9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:camera-image-fill" /></template>
