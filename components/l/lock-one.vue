<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/y6_qflbqc.css';
import '../../css/a/al96yu44v.css';
import '../../css/y/ycelqpu_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="y6_qflbqc"/><path class="al96yu44v"/><path class="ycelqpu_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:lock-one" /></template>
