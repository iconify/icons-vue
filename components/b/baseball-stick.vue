<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfrybph_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="gfrybph_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:baseball-stick" /></template>
