<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iygen8b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iygen8b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-distribute-center-sharp" /></template>
