<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt5219fsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="qt5219fsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:column-decrease" /></template>
