<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/t/tn0h24bih.css';
import '../../css/t/ti1fmsbsz.css';
import '../../css/h/h8xgiibmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="tn0h24bih"/><path class="ti1fmsbsz"/><path class="h8xgiibmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:facial-cleanser" /></template>
