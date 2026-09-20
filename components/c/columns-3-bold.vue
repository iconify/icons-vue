<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l10mnouwk.css';
import '../../css/r/rt2zemb8t.css';
import '../../css/d/d8iz-8b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l10mnouwk"/><path class="rt2zemb8t"/><path class="d8iz-8b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-3-bold" /></template>
