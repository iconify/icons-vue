<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p18b64bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="p18b64bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bookcase" /></template>
