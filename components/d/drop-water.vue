<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufy_ol7bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ufy_ol7bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:drop-water" /></template>
