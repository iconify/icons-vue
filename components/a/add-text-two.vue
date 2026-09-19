<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/h/hrq90hfel.css';
import '../../css/v/vnw7s2b5o.css';
import '../../css/m/mm_zeetyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="hrq90hfel"/><path class="vnw7s2b5o"/><path class="mm_zeetyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:add-text-two" /></template>
