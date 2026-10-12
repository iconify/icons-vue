<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m71trac1c.css';
import '../../css/o/ocri1_tge.css';
import '../../css/o/oqn1-4bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m71trac1c"/><path class="ocri1_tge"/><path clip-rule="evenodd" class="oqn1-4bbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cpu-duotone" /></template>
