<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3349nbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="r3349nbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-two-left-right" /></template>
