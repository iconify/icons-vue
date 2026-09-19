<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/b/bcd2-ib8g.css';
import '../../css/p/pqa51l3ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="y6f0jibvm"/><path class="bcd2-ib8g"/><path class="pqa51l3ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:circle-right-up" /></template>
