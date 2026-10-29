<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dooz9ot8q.css';
import '../../css/n/n8dsurkgv.css';
import '../../css/e/etqnjha5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="dooz9ot8q"/><path class="n8dsurkgv wm-a"/><path class="etqnjha5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:brain-duo" /></template>
