<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/d/dkii0rb8z.css';
import '../../css/n/np_5idvxc.css';
import '../../css/y/yma165b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="dkii0rb8z"/><path class="np_5idvxc"/><path class="yma165b7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:layout-two" /></template>
