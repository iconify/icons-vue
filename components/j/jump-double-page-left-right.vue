<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwbh-cbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="mwbh-cbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:jump-double-page-left-right" /></template>
