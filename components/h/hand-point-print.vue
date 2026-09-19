<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/w/wff_8iblo.css';
import '../../css/e/ecyz1ac2f.css';
import '../../css/k/k3w14tb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><g class="nctb2ac4r"><path class="wff_8iblo"/><path class="ecyz1ac2f"/></g><path clip-rule="evenodd" class="k3w14tb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:hand-point-print" /></template>
