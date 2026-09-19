<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zig2q4ohe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="zig2q4ohe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-down" /></template>
