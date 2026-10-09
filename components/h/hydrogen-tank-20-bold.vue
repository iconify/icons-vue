<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hat3vrldk.css';
import '../../css/j/jj7ew2vkc.css';
import '../../css/f/fztmdkzpk.css';
import '../../css/z/zbfwylorj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hat3vrldk"/><path class="jj7ew2vkc"/><path class="fztmdkzpk"/><path class="zbfwylorj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-tank-20-bold" /></template>
