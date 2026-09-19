<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bc2l054ta.css';
import '../../css/w/w_qvpc58d.css';
import '../../css/f/ffj0jbcke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bc2l054ta"/><path class="w_qvpc58d"/><path class="ffj0jbcke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:baseball-bat-duo" /></template>
