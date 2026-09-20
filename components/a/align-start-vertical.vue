<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an-ar2bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an-ar2bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-start-vertical" /></template>
