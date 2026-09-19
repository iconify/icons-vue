<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzvs8lbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="pzvs8lbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bank" /></template>
