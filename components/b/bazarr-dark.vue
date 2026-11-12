<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i92akobfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i92akobfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bazarr-dark" /></template>
