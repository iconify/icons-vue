<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z58vj_vfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z58vj_vfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:location-compass-2-remix" /></template>
