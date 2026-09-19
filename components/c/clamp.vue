<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdtur3rmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="hdtur3rmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:clamp" /></template>
