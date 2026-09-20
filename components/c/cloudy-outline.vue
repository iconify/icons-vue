<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgr40eb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vgr40eb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:cloudy-outline" /></template>
