<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srt0sd2qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srt0sd2qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery-full-sharp" /></template>
