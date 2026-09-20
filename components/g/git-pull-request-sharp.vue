<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhmtq29kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhmtq29kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:git-pull-request-sharp" /></template>
