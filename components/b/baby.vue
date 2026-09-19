<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apvclab6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="apvclab6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:baby" /></template>
