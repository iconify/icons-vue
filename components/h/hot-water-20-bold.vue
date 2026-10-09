<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ripftlb_v.css';
import '../../css/h/hwfolek5p.css';
import '../../css/i/i07ips82d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ripftlb_v"/><path class="hwfolek5p"/><path class="i07ips82d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-water-20-bold" /></template>
