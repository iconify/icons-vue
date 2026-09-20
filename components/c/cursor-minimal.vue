<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_4j996vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_4j996vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cursor-minimal" /></template>
