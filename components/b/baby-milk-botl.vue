<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_1eaeb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="y_1eaeb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:baby-milk-botl" /></template>
