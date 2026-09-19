<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ar3461yhb.css';
import '../../css/l/lw3fvdb0h.css';
import '../../css/m/m27mn3bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ar3461yhb"/><path class="lw3fvdb0h"/><path class="m27mn3bit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:fire-1" /></template>
