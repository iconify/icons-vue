<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aw9ln9brz.css';
import '../../css/g/gmg2hcb-r.css';
import '../../css/x/x5-ac1bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aw9ln9brz"/><path class="gmg2hcb-r"/><path clip-rule="evenodd" class="x5-ac1bzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:donut-bold" /></template>
