<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwu--hqpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rwu--hqpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:exclamation-triangle-bold" /></template>
