<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-uaddbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="e-uaddbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:game-1" /></template>
