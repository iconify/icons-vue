<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tparw7a_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="tparw7a_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-three-way-2" /></template>
