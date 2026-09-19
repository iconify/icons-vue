<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l3wpbsbfr.css';
import '../../css/l/lahmkgb2w.css';
import '../../css/y/yk9b1vafc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="l3wpbsbfr"/><path class="lahmkgb2w"/><path class="yk9b1vafc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:fireworks" /></template>
