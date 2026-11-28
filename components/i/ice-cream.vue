<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n07l6ebha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n07l6ebha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ice-cream" /></template>
