<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_bf-10yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u_bf-10yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:basket-arrow-right" /></template>
