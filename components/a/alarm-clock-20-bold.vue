<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnqtbnznq.css';
import '../../css/h/hq96i1lwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xnqtbnznq"/><path class="hq96i1lwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alarm-clock-20-bold" /></template>
