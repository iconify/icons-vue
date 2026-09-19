<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxx3h--im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="gxx3h--im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-shuffle" /></template>
