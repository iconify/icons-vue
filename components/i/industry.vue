<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tns3obmll.css';
import '../../css/r/rimbr1eku.css';
import '../../css/b/bnn-vab-g.css';
import '../../css/m/mdoyqib5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="tns3obmll"/><path clip-rule="evenodd" class="rimbr1eku"/><path class="bnn-vab-g"/><path class="mdoyqib5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:industry" /></template>
