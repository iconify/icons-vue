<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vex75ssgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vex75ssgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:history" /></template>
