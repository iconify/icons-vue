<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow7ny9x4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="ow7ny9x4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:hand-switch" /></template>
