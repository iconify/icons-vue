<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r6i16ds0i.css';
import '../../css/j/jptd4uorv.css';
import '../../css/n/nnas63vml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="r6i16ds0i"/><path class="jptd4uorv"/><path class="nnas63vml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:globe-earth" /></template>
