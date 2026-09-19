<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6lsvzbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="i6lsvzbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:flower-pot" /></template>
