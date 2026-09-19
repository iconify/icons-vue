<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gwzldfrvf.css';
import '../../css/m/mx362vb_b.css';
import '../../css/s/s3a1y7bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="gwzldfrvf"/><path class="mx362vb_b"/><path class="s3a1y7bdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:doc-search" /></template>
