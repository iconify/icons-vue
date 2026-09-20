<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_hre3uoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_hre3uoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:diamond-gem" /></template>
