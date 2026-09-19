<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxi3vfcsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="wxi3vfcsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:jump-backward" /></template>
