<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lzttcq10q.css';
import '../../css/g/g_3i-5a_q.css';
import '../../css/b/bbj5cibiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lzttcq10q"/><path class="g_3i-5a_q wm-a"/><path class="bbj5cibiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:banknote-duo" /></template>
