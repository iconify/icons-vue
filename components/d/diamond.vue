<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdy_rh-at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="bdy_rh-at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:diamond" /></template>
