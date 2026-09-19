<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/galaf1zad.css';
import '../../css/p/pt9b1tb7n.css';
import '../../css/s/s5z_srtaj.css';
import '../../css/j/jko7jdb1p.css';
import '../../css/k/k1uq304yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="galaf1zad"/><path class="pt9b1tb7n"/><path class="s5z_srtaj"/><path class="jko7jdb1p"/><circle transform="matrix(0 -1 -1 0 10 14)" class="k1uq304yb"/><circle transform="matrix(0 -1 -1 0 16 14)" class="k1uq304yb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:download-web" /></template>
