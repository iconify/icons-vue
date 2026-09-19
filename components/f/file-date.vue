<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/oy94ivrbs.css';
import '../../css/t/thxofh4mb.css';
import '../../css/g/g9p4dbc2n.css';
import '../../css/t/ti507gz5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="oy94ivrbs"/><path class="thxofh4mb"/><circle class="g9p4dbc2n"/><path class="ti507gz5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:file-date" /></template>
