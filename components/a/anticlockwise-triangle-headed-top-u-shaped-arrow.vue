<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ievw0_bxs.css';
import '../../css/x/x5oypsb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ievw0_bxs"/><path class="x5oypsb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:anticlockwise-triangle-headed-top-u-shaped-arrow" /></template>
