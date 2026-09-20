<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w03w44bva.css';
import '../../css/h/hq0wtlbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w03w44bva"/><path class="hq0wtlbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bicycle-wrench" /></template>
