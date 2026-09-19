<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnr0-ylgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="nnr0-ylgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bookmark" /></template>
