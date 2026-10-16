<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w01dflzvf.css';
import '../../css/k/kk93h00zz.css';
import '../../css/g/gdnaw35gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="kk93h00zz"/><path class="gdnaw35gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-histogram-20-bold" /></template>
