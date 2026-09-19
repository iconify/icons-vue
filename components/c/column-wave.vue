<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti7ff3-an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ti7ff3-an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:column-wave" /></template>
