<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m2blynbna.css';
import '../../css/o/ot_tbvbcc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjQPqWdiy"><g class="s9cl3zbei"><path class="m2blynbna"/><path class="ot_tbvbcc"/></g></mask></defs><path mask="url(#SVGjQPqWdiy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:facetime" /></template>
