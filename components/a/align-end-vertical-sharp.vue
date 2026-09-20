<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msh-i_byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msh-i_byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-end-vertical-sharp" /></template>
