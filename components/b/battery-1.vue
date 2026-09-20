<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulaanbc5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulaanbc5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery-1" /></template>
