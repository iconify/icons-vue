<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmejw90ec.css';
import '../../css/b/b8av53bdl.css';
import '../../css/b/bncxwo81m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fmejw90ec"/><path class="b8av53bdl"/><path class="bncxwo81m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-albums" /></template>
