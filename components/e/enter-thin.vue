<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fii_z8bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fii_z8bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:enter-thin" /></template>
