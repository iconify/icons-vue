<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e5j0jpbhj.css';
import '../../css/o/o8n-38x0t.css';
import '../../css/e/efivi8c9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path clip-rule="evenodd" class="e5j0jpbhj"/><path class="o8n-38x0t"/><path class="efivi8c9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:diamond" /></template>
