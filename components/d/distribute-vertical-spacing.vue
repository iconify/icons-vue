<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3ivccum.css';
import '../../css/t/taetgzrim.css';
import '../../css/a/augjm-bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="taetgzrim"/><path class="augjm-bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:distribute-vertical-spacing" /></template>
