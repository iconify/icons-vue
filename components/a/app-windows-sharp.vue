<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o91b5sbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o91b5sbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:app-windows-sharp" /></template>
