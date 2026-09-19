<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcv25ub_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="jcv25ub_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:circle-o" /></template>
