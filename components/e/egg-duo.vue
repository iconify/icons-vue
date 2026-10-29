<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/eghilk5zd.css';
import '../../css/t/t_iyb2b1h.css';
import '../../css/p/pez66rbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="eghilk5zd"/><path class="t_iyb2b1h wm-a"/><path class="pez66rbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:egg-duo" /></template>
