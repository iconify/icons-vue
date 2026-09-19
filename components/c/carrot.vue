<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/di-pxlb5e.css';
import '../../css/v/v25hqabft.css';
import '../../css/w/wfk4993lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="di-pxlb5e"/><path class="v25hqabft"/><path class="wfk4993lu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:carrot" /></template>
