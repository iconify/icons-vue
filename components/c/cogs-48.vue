<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxk-14-gk.css';
import '../../css/r/r58q_lbbh.css';
import '../../css/f/fn2c-okpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fxk-14-gk"/><path class="r58q_lbbh"/><path class="fn2c-okpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cogs-48" /></template>
