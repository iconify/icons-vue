<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i03ibwbly.css';
import '../../css/n/n1sguyb9y.css';
import '../../css/l/l520w2onl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i03ibwbly"/><path class="n1sguyb9y"/><path class="l520w2onl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gallery-horizontal-duotone" /></template>
