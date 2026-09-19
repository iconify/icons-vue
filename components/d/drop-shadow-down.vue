<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/s/s-ptppb3j.css';
import '../../css/e/e6jd5wfjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path clip-rule="evenodd" class="s-ptppb3j"/><path class="e6jd5wfjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:drop-shadow-down" /></template>
