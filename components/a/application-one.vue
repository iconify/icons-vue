<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/a/a1l92fp8o.css';
import '../../css/r/rv_3mobsj.css';
import '../../css/d/dnhbys-pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="a1l92fp8o"/><path class="rv_3mobsj"/><path class="dnhbys-pl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:application-one" /></template>
