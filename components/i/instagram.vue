<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l6-iy8s0j.css';
import '../../css/c/cqteb8bfj.css';
import '../../css/v/vd35ges3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l6-iy8s0j"/><path class="cqteb8bfj"/><path class="vd35ges3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:instagram" /></template>
