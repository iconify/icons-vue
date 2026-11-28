<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcxu_ls2r.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g41oqhzpy.css';
import '../../css/i/ixg3tzbda.css';
import '../../css/m/mgpehfb1a.css';
import '../../css/w/wofl3qa7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcxu_ls2r secondary"/><g class="dt0cm9dhy primary"><path class="g41oqhzpy"/><path class="ixg3tzbda"/><path class="mgpehfb1a"/><path class="wofl3qa7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-search-duo" /></template>
