<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/q/qg9w3n3bs.css';
import '../../css/s/s8127tbcg.css';
import '../../css/k/k76zracww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="qg9w3n3bs"/><ellipse class="s8127tbcg"/><path class="k76zracww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:database" /></template>
