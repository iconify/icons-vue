<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/g9ec-ub-g.css';
import '../../css/g/gp4cu5h2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="d2kvgvbvc"><path class="g9ec-ub-g"/><path class="gp4cu5h2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:drag" /></template>
