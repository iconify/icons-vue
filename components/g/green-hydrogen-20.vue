<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igszs0yyx.css';
import '../../css/r/r_cx60bme.css';
import '../../css/d/dvybr6c4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="igszs0yyx"/><path class="r_cx60bme"/><path class="dvybr6c4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-hydrogen-20" /></template>
