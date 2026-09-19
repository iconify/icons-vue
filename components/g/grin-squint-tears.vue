<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rnf5o38_t.css';
import '../../css/g/gkw1zgb3s.css';
import '../../css/l/l1y_x7bjg.css';
import '../../css/h/h61_l9m8l.css';
import '../../css/j/j2pzxqiat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rnf5o38_t"/><path clip-rule="evenodd" class="gkw1zgb3s"/><path class="l1y_x7bjg"/><path class="h61_l9m8l"/><path class="j2pzxqiat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:grin-squint-tears" /></template>
