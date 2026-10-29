<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/l/l8wsaryhf.css';
import '../../css/o/o0pmho3fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="l8wsaryhf"/><path class="o0pmho3fz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:binary" /></template>
