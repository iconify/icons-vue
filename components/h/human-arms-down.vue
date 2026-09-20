<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsn85pbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsn85pbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:human-arms-down" /></template>
