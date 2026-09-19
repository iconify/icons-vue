<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8a-ns-2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="u8a-ns-2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:hospital" /></template>
