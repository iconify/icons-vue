<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho4bgebya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho4bgebya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-distribute-start-sharp" /></template>
