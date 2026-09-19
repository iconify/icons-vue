<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnpdkbc0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="jnpdkbc0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-resize-5" /></template>
