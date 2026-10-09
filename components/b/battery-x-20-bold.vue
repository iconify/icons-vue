<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jogeij0zr.css';
import '../../css/k/kwe73qles.css';
import '../../css/v/vivou8bgm.css';
import '../../css/c/cejnnhkdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jogeij0zr"/><path class="kwe73qles"/><path class="vivou8bgm"/><path class="cejnnhkdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-x-20-bold" /></template>
