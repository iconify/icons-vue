<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/whwpro6ey.css';
import '../../css/f/fyssiwbsm.css';
import '../../css/o/olzrecbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="whwpro6ey"/><path class="fyssiwbsm"/><path class="olzrecbio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:key-square-duotone" /></template>
