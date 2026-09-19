<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wip14ubiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="wip14ubiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bomb-2" /></template>
