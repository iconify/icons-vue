<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvufwdbic.css';
import '../../css/r/r_u1-tb8p.css';
import '../../css/h/h8ej8rbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kvufwdbic"/><path class="r_u1-tb8p"/><path class="h8ej8rbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cctv-20" /></template>
