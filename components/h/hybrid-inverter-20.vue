<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi5qd16vh.css';
import '../../css/v/v7zpq2cvm.css';
import '../../css/o/o76juu94h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hi5qd16vh"/><path class="v7zpq2cvm"/><path class="o76juu94h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hybrid-inverter-20" /></template>
