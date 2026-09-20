<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp93dz86h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp93dz86h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:drag-horizontal-expressive" /></template>
