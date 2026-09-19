<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s392k2bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s392k2bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:hammer-and-wrench" /></template>
