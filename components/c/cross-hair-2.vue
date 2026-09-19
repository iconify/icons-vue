<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ued2yndek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ued2yndek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cross-hair-2" /></template>
