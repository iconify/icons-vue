<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4aowzzft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="i4aowzzft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-left" /></template>
