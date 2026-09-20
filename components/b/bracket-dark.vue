<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbb582b_y.css';
import '../../css/o/onr57qb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fbb582b_y"/><path class="onr57qb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bracket-dark" /></template>
