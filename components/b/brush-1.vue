<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiako2bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="jiako2bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:brush-1" /></template>
