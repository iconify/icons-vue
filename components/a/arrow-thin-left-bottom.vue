<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdjq8sbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="tdjq8sbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-thin-left-bottom" /></template>
