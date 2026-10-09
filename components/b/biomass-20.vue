<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucvn8mbai.css';
import '../../css/k/k220q4beo.css';
import '../../css/j/j2pm5abdo.css';
import '../../css/l/l2mw_ubua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ucvn8mbai"/><path class="k220q4beo"/><path class="j2pm5abdo"/><path class="l2mw_ubua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biomass-20" /></template>
