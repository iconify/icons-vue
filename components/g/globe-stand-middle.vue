<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ys5md9n0w.css';
import '../../css/z/zkrbpcbvx.css';
import '../../css/k/k_gphygrl.css';
import '../../css/f/fktx6ibcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ys5md9n0w"/><path class="zkrbpcbvx"/><path class="k_gphygrl"/><path clip-rule="evenodd" class="fktx6ibcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:globe-stand-middle" /></template>
