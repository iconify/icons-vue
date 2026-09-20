<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4bp55b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4bp55b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-circle-clockwise-expressive" /></template>
