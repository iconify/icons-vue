<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqax-6b-d.css';
import '../../css/k/ks0qo9bbe.css';
import '../../css/v/vorlg-byp.css';
import '../../css/y/yeb121b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="ks0qo9bbe"/><path class="vorlg-byp"/><path class="yeb121b_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:lipstick" /></template>
