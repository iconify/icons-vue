<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztr00xb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ztr00xb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:barrier" /></template>
