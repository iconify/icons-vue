<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/a/aapx_rtjc.css';
import '../../css/n/nv8c4nb5x.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGN3k3edTs"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="aapx_rtjc"/><path class="nv8c4nb5x"/></g></mask></defs><circle mask="url(#SVGN3k3edTs)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:leaf-circle-filled" /></template>
