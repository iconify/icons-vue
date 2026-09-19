<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnzczubny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pnzczubny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:briefcase-1" /></template>
