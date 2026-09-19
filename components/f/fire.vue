<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q93rtebqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="q93rtebqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fire" /></template>
