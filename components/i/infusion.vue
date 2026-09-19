<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/w19n41b8s.css';
import '../../css/z/zslw-jbti.css';
import '../../css/g/g07kgbb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="w19n41b8s"/><path class="zslw-jbti"/><path class="g07kgbb_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:infusion" /></template>
