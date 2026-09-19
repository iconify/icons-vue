<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/j/jcxlm2b2l.css';
import '../../css/m/mlzal26cj.css';
import '../../css/v/vr7vsou9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="jcxlm2b2l"/><path clip-rule="evenodd" class="mlzal26cj"/><path class="vr7vsou9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:file-pdf" /></template>
