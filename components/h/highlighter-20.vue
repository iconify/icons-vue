<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmo5pdb9h.css';
import '../../css/p/p5fk5_2cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kmo5pdb9h"/><path class="p5fk5_2cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:highlighter-20" /></template>
