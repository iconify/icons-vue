<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/d/dl_ofsy9w.css';
import '../../css/s/sjb29en2p.css';
import '../../css/p/pytt3n7gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="dl_ofsy9w"/><path class="sjb29en2p"/><path class="pytt3n7gc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:discount" /></template>
