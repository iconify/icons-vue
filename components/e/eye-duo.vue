<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/koh4mu49t.css';
import '../../css/h/hbi8hhkfx.css';
import '../../css/o/oqf382uiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="koh4mu49t"/><path class="hbi8hhkfx wm-a"/><path class="oqf382uiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:eye-duo" /></template>
