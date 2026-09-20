<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hjzzbm_-c.css';
import '../../css/k/k7986xb3g.css';
import '../../css/e/ejl_x_40g.css';
import '../../css/z/zwgti06wg.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="hjzzbm_-c"/><path clip-rule="evenodd" class="k7986xb3g"/><path clip-rule="evenodd" class="ejl_x_40g"/><path class="zwgti06wg"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:calendar-circle-filled" /></template>
