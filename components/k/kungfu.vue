<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btx30rb9t.css';
import '../../css/a/adk1a1f8p.css';
import '../../css/y/yx977ubbo.css';
import '../../css/m/my4dskblt.css';
import '../../css/r/r_ykrfbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="btx30rb9t"><path class="adk1a1f8p"/><path class="yx977ubbo"/><path class="my4dskblt"/><path class="r_ykrfbmv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:kungfu" /></template>
