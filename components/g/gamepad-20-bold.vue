<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0lzq_bbj.css';
import '../../css/s/s_30dcbkg.css';
import '../../css/u/ujgabjbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n0lzq_bbj"/><path class="s_30dcbkg"/><path class="ujgabjbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gamepad-20-bold" /></template>
