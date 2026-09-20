<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lia6c03rv.css';
import '../../css/t/tyqxlrbzk.css';
import '../../css/e/efke-wbwi.css';
import '../../css/r/rma5_ql1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lia6c03rv"/><path class="tyqxlrbzk"/><path class="efke-wbwi"/><path class="rma5_ql1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-4-line-duotone" /></template>
