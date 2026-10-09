<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtsgfacfk.css';
import '../../css/b/bzc7trb_y.css';
import '../../css/n/nwz76kjzw.css';
import '../../css/h/hztb-052z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wtsgfacfk"/><path class="bzc7trb_y"/><path class="nwz76kjzw"/><path class="hztb-052z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:concentrated-solar-20" /></template>
