<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/ghrgblbvq.css';
import '../../css/h/hd-w3pbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="ghrgblbvq wm-k"/><path class="hd-w3pbjc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:align-bottom" /></template>
