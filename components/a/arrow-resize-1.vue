<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrr5k9-6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hrr5k9-6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-resize-1" /></template>
