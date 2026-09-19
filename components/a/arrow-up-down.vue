<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwic0_bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="rwic0_bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-up-down" /></template>
