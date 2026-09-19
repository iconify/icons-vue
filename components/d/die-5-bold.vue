<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbt0vhszc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hbt0vhszc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:die-5-bold" /></template>
