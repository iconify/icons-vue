<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aum7pfzqi.css';
import '../../css/l/leb4hvjgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aum7pfzqi"/><path class="leb4hvjgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-days-20-bold" /></template>
