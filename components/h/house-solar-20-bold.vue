<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iur812moa.css';
import '../../css/y/y40w3sucp.css';
import '../../css/o/o6x3htbqm.css';
import '../../css/r/rzkosvb-d.css';
import '../../css/z/zkili02bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iur812moa"/><path class="y40w3sucp"/><path class="o6x3htbqm"/><path class="rzkosvb-d"/><path class="zkili02bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-solar-20-bold" /></template>
