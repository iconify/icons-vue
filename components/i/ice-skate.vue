<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rl1c9ibxq.css';
import '../../css/b/be0n_c97x.css';
import '../../css/p/p_aomcnvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rl1c9ibxq"/><path class="be0n_c97x"/><path class="p_aomcnvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:ice-skate" /></template>
