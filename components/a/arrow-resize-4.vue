<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdit7nflt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fdit7nflt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-resize-4" /></template>
