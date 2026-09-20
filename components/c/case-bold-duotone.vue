<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/q/qlhqa5a1y.css';
import '../../css/x/xhzturs6n.css';
import '../../css/u/ub62qzant.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="qlhqa5a1y"/><path class="xhzturs6n"/></g><path clip-rule="evenodd" class="ub62qzant"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-bold-duotone" /></template>
