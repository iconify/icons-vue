<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf6vixbyo.css';
import '../../css/q/qhl_bsc2l.css';
import '../../css/j/j4fy5j07e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sf6vixbyo"/><path class="qhl_bsc2l"/><path class="j4fy5j07e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:compreface" /></template>
