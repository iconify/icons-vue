<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtemedn_h.css';
import '../../css/y/y1jnin_gq.css';
import '../../css/r/rl-2a6bga.css';
import '../../css/s/srqm21bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rtemedn_h"/><path class="y1jnin_gq"/><path class="rl-2a6bga"/><path class="srqm21bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-cycle-48-bold" /></template>
