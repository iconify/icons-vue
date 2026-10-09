<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8bmplu8s.css';
import '../../css/v/vgb2cgbyg.css';
import '../../css/k/kiw8kob5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l8bmplu8s"/><path class="vgb2cgbyg"/><path class="kiw8kob5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:headset-20-bold" /></template>
