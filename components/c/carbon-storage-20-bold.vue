<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7up3n3tb.css';
import '../../css/i/i_m0zzb6g.css';
import '../../css/g/gg96zrr7d.css';
import '../../css/r/rbr9__bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u7up3n3tb"/><path class="i_m0zzb6g"/><path class="gg96zrr7d"/><path class="rbr9__bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-storage-20-bold" /></template>
