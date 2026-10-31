<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/m/m6-k53ult.css';
import '../../css/p/pyo5dubfh.css';
import '../../css/v/vs3_2yq5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="m6-k53ult"/><path class="pyo5dubfh wm-k"/><path class="vs3_2yq5q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:flag-checkered" /></template>
