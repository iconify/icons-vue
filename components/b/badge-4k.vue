<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px_zwf21l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px_zwf21l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:badge-4k" /></template>
