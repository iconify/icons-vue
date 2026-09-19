<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5f1l6b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="i5f1l6b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-fist-duo" /></template>
