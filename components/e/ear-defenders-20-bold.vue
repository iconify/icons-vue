<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p480i1bck.css';
import '../../css/c/c9n0mybal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p480i1bck"/><path class="c9n0mybal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ear-defenders-20-bold" /></template>
