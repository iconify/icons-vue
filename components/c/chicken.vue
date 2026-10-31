<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg_d14xro.css';
import '../../css/h/hube6c-_l.css';
import '../../css/u/u7vstwb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="mg_d14xro"/><path class="hube6c-_l"/><path class="u7vstwb-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:chicken" /></template>
