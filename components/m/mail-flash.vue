<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnks6dbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnks6dbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mail-flash" /></template>
