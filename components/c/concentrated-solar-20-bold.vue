<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrwx2vbbl.css';
import '../../css/n/na2wn5bjc.css';
import '../../css/a/a0rbz25oc.css';
import '../../css/o/o4upegzaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hrwx2vbbl"/><path class="na2wn5bjc"/><path class="a0rbz25oc"/><path class="o4upegzaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:concentrated-solar-20-bold" /></template>
