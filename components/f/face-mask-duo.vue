<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b3_b6jb_f.css';
import '../../css/h/h8bbbszdv.css';
import '../../css/a/a6ey7sbng.css';
import '../../css/c/ci5_d5hwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b3_b6jb_f"/><path class="h8bbbszdv wm-a"/><path class="a6ey7sbng"/><path class="ci5_d5hwo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:face-mask-duo" /></template>
