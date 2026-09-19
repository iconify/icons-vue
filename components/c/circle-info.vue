<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f221h1bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="f221h1bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-info" /></template>
