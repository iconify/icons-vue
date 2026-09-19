<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uonzi7l5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uonzi7l5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face4" /></template>
