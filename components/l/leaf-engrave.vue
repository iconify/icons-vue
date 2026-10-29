<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bvhvd8q7c.css';
import '../../css/r/rddu-sewe.css';
import '../../css/u/uu1_fv33n.css';
import '../../css/p/pg6c6hbqu.css';
import '../../css/m/mp77goa1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bvhvd8q7c wm-k"/><path class="rddu-sewe wm-a"/><path class="uu1_fv33n wm-shadow"/><path class="pg6c6hbqu wm-k"/><path class="mp77goa1w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:leaf-engrave" /></template>
