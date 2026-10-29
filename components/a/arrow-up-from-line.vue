<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/c/c3-qehboe.css';
import '../../css/f/frj9uobrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="c3-qehboe"/><path class="frj9uobrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-up-from-line" /></template>
