<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hw927lbmm.css';
import '../../css/d/dkfws9ftw.css';
import '../../css/m/m9-4k6y9w.css';
import '../../css/p/pf05l3ymp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hw927lbmm"/><path class="dkfws9ftw wm-s"/><path class="m9-4k6y9w"/><path class="pf05l3ymp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-sun-rain-duo" /></template>
