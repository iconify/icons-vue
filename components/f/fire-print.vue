<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/x/x5dw6db5g.css';
import '../../css/i/iu2t7stsp.css';
import '../../css/v/vm2olqtiv.css';
import '../../css/m/mociiybqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path class="x5dw6db5g"/><path clip-rule="evenodd" class="iu2t7stsp"/></g><path clip-rule="evenodd" class="vm2olqtiv"/><path clip-rule="evenodd" class="mociiybqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:fire-print" /></template>
