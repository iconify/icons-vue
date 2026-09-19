<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5kdt5bwm.css';
import '../../css/l/lsg5j7ibl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p5kdt5bwm"/><path class="lsg5j7ibl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:caret-up-circle-outline" /></template>
