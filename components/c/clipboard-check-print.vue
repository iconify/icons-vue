<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/a/a4imupo2v.css';
import '../../css/f/fxe-jccqn.css';
import '../../css/s/st9amz82z.css';
import '../../css/q/qptf5_b3w.css';
import '../../css/l/l4qucyn3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path clip-rule="evenodd" class="a4imupo2v"/><path class="fxe-jccqn"/></g><path clip-rule="evenodd" class="st9amz82z"/><path clip-rule="evenodd" class="qptf5_b3w"/><path clip-rule="evenodd" class="l4qucyn3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:clipboard-check-print" /></template>
