<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cv_bv5bue.css';
import '../../css/a/a_egs8b1e.css';
import '../../css/s/sencbj8te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cv_bv5bue"/><path class="a_egs8b1e"/><path class="sencbj8te"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-bold-duotone" /></template>
