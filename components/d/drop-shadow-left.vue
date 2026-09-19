<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/o/oxdeg8v4h.css';
import '../../css/m/m8g3srp9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path clip-rule="evenodd" class="oxdeg8v4h"/><path class="m8g3srp9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:drop-shadow-left" /></template>
