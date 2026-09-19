<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/urswrcbmq.css';
import '../../css/g/g_xqm8rqg.css';
import '../../css/k/kv3u5obgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><circle class="urswrcbmq"/><circle class="g_xqm8rqg"/><path class="kv3u5obgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lifesaver-stroke-16" /></template>
