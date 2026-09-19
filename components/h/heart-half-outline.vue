<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omrej3mio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="omrej3mio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-half-outline" /></template>
