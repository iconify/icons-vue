<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwjyk7hlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="gwjyk7hlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-thick-left" /></template>
