<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km2fl-ght.css';
import '../../css/d/dud29m81y.css';
import '../../css/a/ao3jx10od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="km2fl-ght"/><path class="dud29m81y"/><path class="ao3jx10od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-histogram-20" /></template>
