<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-kxx2bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-kxx2bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:badge-5k-sharp" /></template>
