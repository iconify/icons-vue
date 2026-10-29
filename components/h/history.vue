<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n2kxb8blp.css';
import '../../css/i/ip9ou-86q.css';
import '../../css/o/opvnhmoea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n2kxb8blp"/><path class="ip9ou-86q"/><path class="opvnhmoea wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:history" /></template>
