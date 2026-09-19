<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/z/z8_mqecnt.css';
import '../../css/y/ydag_ubap.css';
import '../../css/o/oe_umpfom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="z8_mqecnt"/><path class="ydag_ubap"/><path class="oe_umpfom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:caution" /></template>
