<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr04_fblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr04_fblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horizontal-rotate-counterclockwise" /></template>
