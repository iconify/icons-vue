<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obdrwxfti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="obdrwxfti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:disc-play-2" /></template>
