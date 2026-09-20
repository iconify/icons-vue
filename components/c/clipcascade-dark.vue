<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugpc5acxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugpc5acxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clipcascade-dark" /></template>
