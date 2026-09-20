<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fld1fknfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fld1fknfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:home" /></template>
