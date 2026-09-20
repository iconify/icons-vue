<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilfss7bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilfss7bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:debug-pause" /></template>
