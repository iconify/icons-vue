<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utbu3d6ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utbu3d6ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:achievement-variant-outline" /></template>
