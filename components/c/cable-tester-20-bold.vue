<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp_etqb_g.css';
import '../../css/i/igjclji7g.css';
import '../../css/r/rydg37bln.css';
import '../../css/o/or6bu4_ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xp_etqb_g"/><path class="igjclji7g"/><path class="rydg37bln"/><path class="or6bu4_ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-tester-20-bold" /></template>
