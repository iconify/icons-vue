<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bkaq4tblo.css';
import '../../css/p/pny223f3z.css';
import '../../css/s/smdysmmqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bkaq4tblo"/><path class="pny223f3z"/><path class="smdysmmqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image-depth" /></template>
