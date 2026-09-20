<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0f7grb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i0f7grb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kibana-light" /></template>
