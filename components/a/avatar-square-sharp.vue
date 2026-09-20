<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z61j5nz5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z61j5nz5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:avatar-square-sharp" /></template>
