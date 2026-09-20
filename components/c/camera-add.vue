<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-tkx6bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-tkx6bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:camera-add" /></template>
