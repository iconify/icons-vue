<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slr3n6bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="slr3n6bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:column-increase" /></template>
