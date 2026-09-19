<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpu81hs1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="dpu81hs1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:head-set" /></template>
