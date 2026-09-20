<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi1mumb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi1mumb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:avatar-circle-x-sharp" /></template>
