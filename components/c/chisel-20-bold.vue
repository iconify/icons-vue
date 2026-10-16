<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbmu3eofk.css';
import '../../css/q/qg7yfsbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jbmu3eofk"/><path class="qg7yfsbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chisel-20-bold" /></template>
