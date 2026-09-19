<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdwgm7vrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cdwgm7vrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:aperture" /></template>
