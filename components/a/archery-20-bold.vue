<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w07o7rb0l.css';
import '../../css/z/z4o_8eb_q.css';
import '../../css/y/yvyc8v67g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w07o7rb0l"/><path class="z4o_8eb_q"/><path class="yvyc8v67g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:archery-20-bold" /></template>
