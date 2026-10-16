<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn0um0h7v.css';
import '../../css/l/lpo20xysi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hn0um0h7v"/><path class="lpo20xysi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:black-start-20-bold" /></template>
