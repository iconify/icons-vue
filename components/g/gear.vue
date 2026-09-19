<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pczyoks0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="pczyoks0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:gear" /></template>
