<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wm7z0fbzo.css';
import '../../css/o/o53n0ib2h.css';
import '../../css/y/y95393_dl.css';
import '../../css/i/i-7a-zb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wm7z0fbzo"/><path class="o53n0ib2h wm-a"/><path class="y95393_dl"/><path class="i-7a-zb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:database-duo" /></template>
