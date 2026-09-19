<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1qm32gsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="c1qm32gsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-fullscreen-2" /></template>
