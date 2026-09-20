<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rx9sfhb0h.css';
import '../../css/u/u3tke38bu.css';
import '../../css/y/ybpq_2f7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rx9sfhb0h"/><path class="u3tke38bu"/><path class="ybpq_2f7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-ring" /></template>
