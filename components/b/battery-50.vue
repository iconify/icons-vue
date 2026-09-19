<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0y0vmcag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="i0y0vmcag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-50" /></template>
