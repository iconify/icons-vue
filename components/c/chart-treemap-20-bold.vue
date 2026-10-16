<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_3tybcwd.css';
import '../../css/u/u3mp5lqgi.css';
import '../../css/x/x-3aazb-g.css';
import '../../css/e/enwjp7ebc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l_3tybcwd"/><path class="u3mp5lqgi"/><path class="x-3aazb-g"/><path class="enwjp7ebc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-treemap-20-bold" /></template>
