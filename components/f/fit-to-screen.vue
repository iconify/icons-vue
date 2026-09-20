<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnob0x5zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnob0x5zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fit-to-screen" /></template>
