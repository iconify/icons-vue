<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtxonkbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtxonkbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-o-circle" /></template>
