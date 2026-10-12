<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v0ktk-1-q.css';
import '../../css/n/nw4f7abft.css';
import '../../css/a/ai741630p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v0ktk-1-q"/><path class="nw4f7abft"/><path class="ai741630p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:diamond-minus-duotone" /></template>
