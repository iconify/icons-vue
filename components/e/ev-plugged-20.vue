<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo7q5s88y.css';
import '../../css/s/s_8gwxbem.css';
import '../../css/q/q7wl5khmr.css';
import '../../css/m/m6p15ub_a.css';
import '../../css/x/xe6_rlbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lo7q5s88y"/><path class="s_8gwxbem"/><path class="q7wl5khmr"/><path class="m6p15ub_a"/><path class="xe6_rlbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-plugged-20" /></template>
