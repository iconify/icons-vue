<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/msz60p3bx.css';
import '../../css/m/mp63jovjl.css';
import '../../css/k/kgmv5bb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="msz60p3bx"/><circle class="mp63jovjl"/><path class="kgmv5bb8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:gauze" /></template>
