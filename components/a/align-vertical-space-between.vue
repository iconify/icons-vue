<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl8h2wwbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl8h2wwbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-space-between" /></template>
