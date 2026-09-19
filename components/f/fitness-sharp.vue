<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7k5gibth.css';
import '../../css/k/kjznt1r2d.css';
import '../../css/o/o-y2m3oef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d7k5gibth"/><path class="kjznt1r2d"/><path class="o-y2m3oef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:fitness-sharp" /></template>
