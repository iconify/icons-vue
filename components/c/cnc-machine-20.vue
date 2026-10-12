<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-khqclun.css';
import '../../css/e/e6u7bf88s.css';
import '../../css/f/f020qv8gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z-khqclun"/><path class="e6u7bf88s"/><path class="f020qv8gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cnc-machine-20" /></template>
