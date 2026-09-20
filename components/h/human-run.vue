<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csliwi17s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csliwi17s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:human-run" /></template>
