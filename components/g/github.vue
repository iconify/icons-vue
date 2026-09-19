<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/q/qv7h2s_bd.css';
import '../../css/f/frnub0hjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="d2kvgvbvc"><path class="qv7h2s_bd"/><path class="frnub0hjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:github" /></template>
