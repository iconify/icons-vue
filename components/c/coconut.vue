<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y993d1bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="y993d1bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:coconut" /></template>
