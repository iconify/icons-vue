<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/albryfbqk.css';
import '../../css/g/g0ke4nyhw.css';
import '../../css/r/rp0c_5bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="albryfbqk"/><path class="g0ke4nyhw"/><path class="rp0c_5bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domain-watchdog" /></template>
