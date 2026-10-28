<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/j/jijs-abeb.css';
import '../../css/b/b4_yy6ggh.css';
import '../../css/k/k7byg-byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="jijs-abeb"/><path class="b4_yy6ggh"/><path class="k7byg-byb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:lock" /></template>
