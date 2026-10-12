<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ic-ypnb0e.css';
import '../../css/v/vco6qb1-p.css';
import '../../css/q/qwy_kna5r.css';
import '../../css/c/cr4zr3btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ic-ypnb0e"/><path class="vco6qb1-p"/><path class="qwy_kna5r"/><path class="cr4zr3btz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-badge-duotone" /></template>
