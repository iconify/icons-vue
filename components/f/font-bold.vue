<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iei8tsbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="iei8tsbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:font-bold" /></template>
