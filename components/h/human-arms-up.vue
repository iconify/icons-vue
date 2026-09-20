<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psu4j2bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psu4j2bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:human-arms-up" /></template>
