<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3a_arbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h3a_arbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crosshairs-1-outline" /></template>
