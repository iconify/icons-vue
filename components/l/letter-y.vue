<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eobp_3bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eobp_3bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-y" /></template>
