<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/efyrmtbde.css';
import '../../css/u/u_07p0rbf.css';
import '../../css/i/ilf33kbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="efyrmtbde"/><path class="u_07p0rbf"/><path class="ilf33kbod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-clock" /></template>
