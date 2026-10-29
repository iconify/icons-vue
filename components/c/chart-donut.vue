<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/l/lslb_f9id.css';
import '../../css/q/qy1ni-bgs.css';
import '../../css/v/v20_eu2nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="lslb_f9id wm-k"/><path class="qy1ni-bgs wm-a"/><path class="v20_eu2nd wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chart-donut" /></template>
