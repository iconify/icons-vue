<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx5kz2dev.css';
import '../../css/k/k98nskc3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jx5kz2dev"/><path class="k98nskc3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charging-schedule-20" /></template>
