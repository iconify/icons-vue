<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw0uxjbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw0uxjbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chart-line-sharp" /></template>
