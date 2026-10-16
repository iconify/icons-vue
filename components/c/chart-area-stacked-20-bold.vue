<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w01dflzvf.css';
import '../../css/b/b6wxp1uvp.css';
import '../../css/u/u5jabkb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="b6wxp1uvp"/><path class="u5jabkb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-area-stacked-20-bold" /></template>
