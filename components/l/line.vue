<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh475k0hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rh475k0hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:line" /></template>
