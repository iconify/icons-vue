<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rrb02niec.css';
import '../../css/e/ecsb1bbva.css';
import '../../css/a/awndadvkq.css';
import '../../css/w/wdnrfxjuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rrb02niec wm-a"/><path class="ecsb1bbva wm-k"/><path class="awndadvkq wm-a"/><path class="wdnrfxjuj wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:firecracker-string-sketch" /></template>
