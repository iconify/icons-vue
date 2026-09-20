<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kpv21hb3o.css';
import '../../css/h/h3d6wbbau.css';
import '../../css/j/jqgrt3b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kpv21hb3o"/><path class="h3d6wbbau"/><path class="jqgrt3b3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-git-branch" /></template>
