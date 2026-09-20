<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw1x60bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw1x60bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hexagon-multiple-outline" /></template>
