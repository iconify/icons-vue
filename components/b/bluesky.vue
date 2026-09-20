<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir1gv_2ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir1gv_2ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bluesky" /></template>
