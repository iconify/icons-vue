<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwwp_sbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="hwwp_sbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mail-box" /></template>
