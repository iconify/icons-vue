<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e6kqonb8o.css';
import '../../css/g/gc1jr4bji.css';
import '../../css/n/n9em5fasb.css';
import '../../css/o/oc_qcrgei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="e6kqonb8o"/><path class="gc1jr4bji wm-a"/><path class="n9em5fasb"/><path class="oc_qcrgei wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:award-duo" /></template>
