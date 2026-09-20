<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj2hjiqls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hj2hjiqls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-one-light" /></template>
