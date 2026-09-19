<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jexdvubgo.css';
import '../../css/n/n8txsybzr.css';
import '../../css/s/s_fib0byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="jexdvubgo"/><path class="n8txsybzr"/><path class="s_fib0byi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:folder-code" /></template>
