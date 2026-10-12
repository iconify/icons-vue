<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mhllb-_9i.css';
import '../../css/j/jr8_gf32b.css';
import '../../css/b/bm6qz-e6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mhllb-_9i"/><path class="jr8_gf32b"/><path class="bm6qz-e6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-horizontal-justify-center-duotone" /></template>
