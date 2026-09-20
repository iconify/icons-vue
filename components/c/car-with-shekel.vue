<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw90mob3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vw90mob3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-with-shekel" /></template>
