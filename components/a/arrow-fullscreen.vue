<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r18bzj1my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="r18bzj1my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-fullscreen" /></template>
