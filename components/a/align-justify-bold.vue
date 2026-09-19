<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obaevwb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="obaevwb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-justify-bold" /></template>
