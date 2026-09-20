<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/c/cg_91gber.css';
import '../../css/r/r1ipski8e.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGOMUD7dfB"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="cg_91gber"/><path class="r1ipski8e"/></g></mask></defs><circle mask="url(#SVGOMUD7dfB)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:fire-circle-filled" /></template>
