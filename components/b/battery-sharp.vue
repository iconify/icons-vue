<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ombxg13qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ombxg13qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery-sharp" /></template>
