<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcia1ds6l.css';
import '../../css/h/hzc3zu61t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pcia1ds6l"/><path class="hzc3zu61t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-flammable-20-bold" /></template>
