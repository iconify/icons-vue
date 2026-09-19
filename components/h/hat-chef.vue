<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyfy9yb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="tyfy9yb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:hat-chef" /></template>
