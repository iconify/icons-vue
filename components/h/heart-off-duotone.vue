<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mbvctibfr.css';
import '../../css/p/p75y43bht.css';
import '../../css/n/n35dlibfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mbvctibfr"/><path class="p75y43bht"/><path class="n35dlibfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:heart-off-duotone" /></template>
