<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6ltpbg0v.css';
import '../../css/t/t_7rprl1m.css';
import '../../css/k/ketn0_oyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g6ltpbg0v"/><path class="t_7rprl1m"/><path class="ketn0_oyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-car-20-bold" /></template>
