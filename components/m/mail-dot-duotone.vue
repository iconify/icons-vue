<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oel4ofb7x.css';
import '../../css/s/shxonjffg.css';
import '../../css/o/ol-n2bb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oel4ofb7x"/><path class="shxonjffg"/><path class="ol-n2bb3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-dot-duotone" /></template>
