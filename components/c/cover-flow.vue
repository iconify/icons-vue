<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/famlpk19j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="famlpk19j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cover-flow" /></template>
