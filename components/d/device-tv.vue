<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkcw5h-pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkcw5h-pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:device-tv" /></template>
