<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl4_75btv.css';
import '../../css/t/tjbpj-bfm.css';
import '../../css/n/nynkg8aut.css';
import '../../css/a/auez8firg.css';
import '../../css/b/bwg1n3b_l.css';
import '../../css/f/fvknzhbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fl4_75btv"/><path class="tjbpj-bfm"/><path class="nynkg8aut"/><path class="auez8firg"/><path class="bwg1n3b_l"/><path class="fvknzhbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heatmap-48-bold" /></template>
