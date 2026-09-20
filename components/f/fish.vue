<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqax-6b-d.css';
import '../../css/i/ivapdzbmk.css';
import '../../css/w/wb367bb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="ivapdzbmk"/><path class="wb367bb3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fish" /></template>
