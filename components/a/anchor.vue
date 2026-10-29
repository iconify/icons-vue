<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/ploa71bki.css';
import '../../css/n/n3rsbi38y.css';
import '../../css/u/u2f_ne4qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ploa71bki wm-a"/><path class="n3rsbi38y"/><path class="u2f_ne4qg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:anchor" /></template>
