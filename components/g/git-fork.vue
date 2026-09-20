<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/b/bn5ilqppl.css';
import '../../css/p/ppzqy-bxa.css';
import '../../css/o/ouxzqo9mb.css';
import '../../css/d/dfqro5y3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="bn5ilqppl"/><circle class="ppzqy-bxa"/><circle class="ouxzqo9mb"/><path class="dfqro5y3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:git-fork" /></template>
