<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j8y588b4d.css';
import '../../css/h/h17v5_bhk.css';
import '../../css/v/v9k9l7b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="j8y588b4d"/><path class="h17v5_bhk"/><path class="v9k9l7b1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:light-switch" /></template>
