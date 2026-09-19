<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy9uw-bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dy9uw-bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cruise" /></template>
