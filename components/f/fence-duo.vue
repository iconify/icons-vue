<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s2gz3mbzi.css';
import '../../css/m/mexbxv5go.css';
import '../../css/s/s53jcxmyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="s2gz3mbzi"/><path class="mexbxv5go wm-a"/><path class="s53jcxmyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fence-duo" /></template>
