<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7juawdew.css';
import '../../css/d/d2axpfabm.css';
import '../../css/m/mmo1ocbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7juawdew"/><path class="d2axpfabm"/><path class="mmo1ocbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-meter-20" /></template>
