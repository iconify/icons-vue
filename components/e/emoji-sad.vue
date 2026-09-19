<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c02b__imu.css';
import '../../css/p/p9-zrkb4g.css';
import '../../css/f/fdpjff5dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c02b__imu"/><path class="p9-zrkb4g"/><path class="fdpjff5dn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:emoji-sad" /></template>
