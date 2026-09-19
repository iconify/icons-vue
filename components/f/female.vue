<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmra16ofi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="dmra16ofi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:female" /></template>
