<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz9_ijixv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz9_ijixv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:airplay" /></template>
