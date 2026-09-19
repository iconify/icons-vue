<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftmvcwbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ftmvcwbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:blur-linear" /></template>
