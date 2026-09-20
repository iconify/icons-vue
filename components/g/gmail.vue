<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clgqjf2qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clgqjf2qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:gmail" /></template>
