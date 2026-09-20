<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwo-zkbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mwo-zkbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:descent-stage" /></template>
