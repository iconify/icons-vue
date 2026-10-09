<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwbb8x53o.css';
import '../../css/m/mufw90bzh.css';
import '../../css/p/pvxhf4bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nwbb8x53o"/><path class="mufw90bzh"/><path class="pvxhf4bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:helideck-20-bold" /></template>
