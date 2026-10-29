<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a16cc9b_a.css';
import '../../css/l/l2bljsbmn.css';
import '../../css/x/x6gd_prso.css';
import '../../css/z/zh_p1cc6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a16cc9b_a"/><path class="l2bljsbmn wm-a"/><path class="x6gd_prso"/><path class="wm-a zh_p1cc6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bug" /></template>
