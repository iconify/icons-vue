<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hi_3yte4a.css';
import '../../css/y/y9dlnubeo.css';
import '../../css/a/ag75s1cpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hi_3yte4a"/><path class="y9dlnubeo"/><path class="ag75s1cpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:dairy" /></template>
