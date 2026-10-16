<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs-1v6bed.css';
import '../../css/x/x4a8ysb7l.css';
import '../../css/w/wkchaul0v.css';
import '../../css/d/dw16-vbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hs-1v6bed"/><path class="x4a8ysb7l"/><path class="wkchaul0v"/><path class="dw16-vbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bench-vice-48-bold" /></template>
