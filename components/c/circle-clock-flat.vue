<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e8psh3biy.css';
import '../../css/n/n-t92abvs.css';
import '../../css/c/c-24taceb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="e8psh3biy"/><path class="n-t92abvs"/><path class="c-24taceb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:circle-clock-flat" /></template>
