<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj1uad_0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nj1uad_0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockprobe-dark" /></template>
