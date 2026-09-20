<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsf2pypry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsf2pypry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:badge-hd-sharp" /></template>
