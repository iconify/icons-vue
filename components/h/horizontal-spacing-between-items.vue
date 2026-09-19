<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/e/e5i876b3q.css';
import '../../css/q/qst3jj07t.css';
import '../../css/c/c5_4__biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="e5i876b3q"/><path class="qst3jj07t"/><path class="c5_4__biv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:horizontal-spacing-between-items" /></template>
