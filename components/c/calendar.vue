<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl54b9bcm.css';
import '../../css/o/oy01ueb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl54b9bcm"/><path class="oy01ueb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:calendar" /></template>
