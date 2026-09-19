<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtynt79qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="rtynt79qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:invert-colors-off" /></template>
