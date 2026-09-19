<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0ll0-snz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s0ll0-snz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-list-bold" /></template>
