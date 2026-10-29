<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gibh68n7x.css';
import '../../css/s/s2uhgxbuo.css';
import '../../css/e/em4t9mizl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gibh68n7x"/><path class="s2uhgxbuo wm-a"/><path class="em4t9mizl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:glass-water-duo" /></template>
