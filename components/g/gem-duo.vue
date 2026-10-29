<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mr0gc7bvl.css';
import '../../css/d/dbqmg1f3w.css';
import '../../css/u/uzvf5obnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mr0gc7bvl"/><path class="dbqmg1f3w"/><path class="uzvf5obnx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gem-duo" /></template>
