<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyajd4b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gyajd4b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hash" /></template>
