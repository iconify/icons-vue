<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fmp-5vctz.css';
import '../../css/m/m9kc8fbca.css';
import '../../css/o/ocqlkk5_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fmp-5vctz"/><path class="m9kc8fbca"/><path class="ocqlkk5_u wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:firecracker" /></template>
