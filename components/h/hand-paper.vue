<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3bt70wlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="d3bt70wlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-paper" /></template>
