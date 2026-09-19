<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vhe_009zr.css';
import '../../css/j/jvk8qniua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="vhe_009zr"/><path clip-rule="evenodd" class="jvk8qniua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:backhand-index-pointing-down-light" /></template>
