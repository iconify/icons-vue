<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9-dj30pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9-dj30pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:discord-solid" /></template>
