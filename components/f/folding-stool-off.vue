<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/dw47yel7y.css';
import '../../css/g/g6an5ei9s.css';
import '../../css/u/u_8_gxjut.css';
import '../../css/l/lva1h7g9t.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g clip-rule="evenodd" class="d2kvgvbvc"><path class="dw47yel7y"/><path class="g6an5ei9s"/><path class="u_8_gxjut"/><path class="lva1h7g9t"/></g><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:folding-stool-off" /></template>
