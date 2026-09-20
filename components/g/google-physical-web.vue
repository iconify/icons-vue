<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7wb0ibza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7wb0ibza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-physical-web" /></template>
