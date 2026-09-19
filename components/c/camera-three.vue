<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/r/rd9mw5o4z.css';
import '../../css/x/x39a_dbqm.css';
import '../../css/u/u4h-v8rsq.css';
import '../../css/l/lsfq8fbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><rect class="rd9mw5o4z"/><path class="x39a_dbqm"/><circle class="u4h-v8rsq"/><path class="lsfq8fbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:camera-three" /></template>
