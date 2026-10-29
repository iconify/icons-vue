<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jxozh2_lw.css';
import '../../css/d/d3y9mw6db.css';
import '../../css/f/fz_84_b9c.css';
import '../../css/b/b1ssu5c-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jxozh2_lw"/><path class="d3y9mw6db"/><path class="fz_84_b9c wm-a"/><path class="b1ssu5c-a wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-bob" /></template>
