<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzk0swxtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzk0swxtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:airplay-sharp" /></template>
