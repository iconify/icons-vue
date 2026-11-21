<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvt1q9bhv.css';
import '../../css/j/jp9nm159y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvt1q9bhv"/><path class="jp9nm159y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:hand-left-outline" /></template>
