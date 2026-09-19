<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/ztd6seb3o.css';
import '../../css/w/wni7cbbjl.css';
import '../../css/b/buhoe6w5z.css';
import '../../css/n/nrouxcbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ztd6seb3o"/><path clip-rule="evenodd" class="wni7cbbjl"/><path class="buhoe6w5z"/><path clip-rule="evenodd" class="nrouxcbcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:check-badge-outline" /></template>
