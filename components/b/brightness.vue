<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et9yusbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="et9yusbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:brightness" /></template>
