<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuoz_bcaq.css';
import '../../css/g/gavnn00vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cuoz_bcaq"/><path class="gavnn00vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:delivery-robot-20" /></template>
