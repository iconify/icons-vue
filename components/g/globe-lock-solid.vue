<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bsuo0en-y.css';
import '../../css/l/lu0o3pjvh.css';
import '../../css/i/ighrvy6qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="bsuo0en-y"/><path class="lu0o3pjvh wm-a"/><path class="ighrvy6qd wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:globe-lock-solid" /></template>
