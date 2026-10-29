<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c8-703b6t.css';
import '../../css/c/clsq4v3-l.css';
import '../../css/j/j-dbpmb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="c8-703b6t"/><path class="clsq4v3-l wm-a"/><path class="j-dbpmb7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bread-duo" /></template>
