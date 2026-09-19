<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fixgzfbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fixgzfbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:die-4-bold" /></template>
