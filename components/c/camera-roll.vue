<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duwc1vbbx.css';
import '../../css/w/w9p-hib0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="duwc1vbbx"/><path class="w9p-hib0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:camera-roll" /></template>
