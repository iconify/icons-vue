<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m0lx_bbbm.css';
import '../../css/b/b9ivx0bck.css';
import '../../css/f/flgkh2bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m0lx_bbbm"/><path class="b9ivx0bck"/><path class="flgkh2bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:graph-ring-duotone" /></template>
