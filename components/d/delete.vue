<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lk4812blb.css';
import '../../css/e/eazx2bcrj.css';
import '../../css/o/o8r2yac7u.css';
import '../../css/i/i3qsavb6m.css';
import '../../css/q/q6janmb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="lk4812blb"/><path class="eazx2bcrj"/><path class="o8r2yac7u"/><path class="i3qsavb6m"/><path class="q6janmb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:delete" /></template>
