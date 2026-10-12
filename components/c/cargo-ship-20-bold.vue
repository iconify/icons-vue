<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw0z3v33o.css';
import '../../css/r/ralbey30g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lw0z3v33o"/><path class="ralbey30g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cargo-ship-20-bold" /></template>
