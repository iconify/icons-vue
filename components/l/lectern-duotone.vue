<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sbtg6tbae.css';
import '../../css/n/nrn9y4vna.css';
import '../../css/q/qo5oo6bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sbtg6tbae"/><path class="nrn9y4vna"/><path class="qo5oo6bzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lectern-duotone" /></template>
