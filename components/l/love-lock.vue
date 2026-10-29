<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pdoe7fa1e.css';
import '../../css/h/h7a9wibzd.css';
import '../../css/c/cu7wb8t0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pdoe7fa1e wm-a"/><path class="h7a9wibzd"/><path class="cu7wb8t0f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:love-lock" /></template>
