<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr5lrxbeo.css';
import '../../css/y/y5hdzhbmr.css';
import '../../css/y/yi3irnyqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="pr5lrxbeo"/><path class="y5hdzhbmr"/><path class="yi3irnyqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-medium-square" /></template>
