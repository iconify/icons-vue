<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q_hr1s_on.css';
import '../../css/w/w_e3nlbsq.css';
import '../../css/l/lhaxnqbla.css';
import '../../css/k/kbpjvngat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="bi12bsetm"><path class="q_hr1s_on"/><path class="w_e3nlbsq"/><path class="lhaxnqbla"/><path class="kbpjvngat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cargo-lock" /></template>
