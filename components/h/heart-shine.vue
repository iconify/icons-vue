<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v3rov_nmk.css';
import '../../css/p/pj530ypns.css';
import '../../css/l/l2hwysa-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v3rov_nmk"/><path clip-rule="evenodd" class="pj530ypns"/><path class="l2hwysa-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-shine" /></template>
