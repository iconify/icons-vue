<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovl0b1-lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ovl0b1-lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-two-way-right" /></template>
