<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/j7n0u1bfa.css';
import '../../css/g/gz5qvg7hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="funnel-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="j7n0u1bfa"/><path class="gz5qvg7hl"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:funnel-outline" /></template>
