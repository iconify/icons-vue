<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m63tckbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="m63tckbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:glass-water" /></template>
