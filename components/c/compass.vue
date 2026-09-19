<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/etqbe4rqk.css';
import '../../css/p/p2t0wu_el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="etqbe4rqk"/><path class="p2t0wu_el"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:compass" /></template>
