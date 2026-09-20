<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/dvssgz61n.css';
import '../../css/e/enu23zbgq.css';
import '../../css/p/parzbjbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dvssgz61n"/><path class="enu23zbgq"/><path class="parzbjbsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-notion" /></template>
