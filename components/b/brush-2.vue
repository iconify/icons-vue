<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9mhcml7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l9mhcml7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:brush-2" /></template>
