<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eei12nfrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="eei12nfrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:jump-page-up-down" /></template>
