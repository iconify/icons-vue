<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/o/obx-q6w6p.css';
import '../../css/l/l0dgq74pp.css';
import '../../css/g/gh0pyjbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="obx-q6w6p"/><path class="l0dgq74pp"/></g><path clip-rule="evenodd" class="gh0pyjbft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-horizontal-bold-duotone" /></template>
