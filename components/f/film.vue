<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkf3q2s5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="mkf3q2s5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:film" /></template>
