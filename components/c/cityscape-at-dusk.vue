<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llrp2r34b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="llrp2r34b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cityscape-at-dusk" /></template>
