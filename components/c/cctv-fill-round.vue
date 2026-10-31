<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkxf86huh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkxf86huh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cctv-fill-round" /></template>
