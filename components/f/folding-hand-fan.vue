<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc5xdf2ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hc5xdf2ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:folding-hand-fan" /></template>
