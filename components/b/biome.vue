<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdp06ek3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":74,"height":74};
const content = `<path class="sdp06ek3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:biome" /></template>
