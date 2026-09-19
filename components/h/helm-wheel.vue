<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuy_jrmro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="nuy_jrmro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:helm-wheel" /></template>
