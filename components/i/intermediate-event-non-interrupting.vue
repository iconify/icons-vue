<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf539cbsg.css';
import '../../css/g/gzff54bpk.css';
import '../../css/u/ucy902b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<g transform="translate(0 995.638)" class="nf539cbsg"><circle class="gzff54bpk"/><circle class="ucy902b6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-non-interrupting" /></template>
