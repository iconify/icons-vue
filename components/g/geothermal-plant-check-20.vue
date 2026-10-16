<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryuntyb6m.css';
import '../../css/d/d2zrzusbd.css';
import '../../css/y/yt1kjcbtq.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ryuntyb6m"/><path class="d2zrzusbd"/><path class="yt1kjcbtq"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geothermal-plant-check-20" /></template>
