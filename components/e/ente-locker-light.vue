<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp1h2bbup.css';
import '../../css/d/d8smgqcqm.css';
import '../../css/k/k4ph6mujc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xp1h2bbup"/><path class="d8smgqcqm"/><path class="k4ph6mujc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ente-locker-light" /></template>
