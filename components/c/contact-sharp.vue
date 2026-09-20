<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1_h6wber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1_h6wber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:contact-sharp" /></template>
