<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dbp6o1bik.css';
import '../../css/y/yfrtf1_-w.css';
import '../../css/f/f51qkfbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dbp6o1bik"/><path class="yfrtf1_-w"/><path class="f51qkfbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:battery-full" /></template>
