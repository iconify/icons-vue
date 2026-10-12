<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjy23_bwm.css';
import '../../css/e/ex-8_4bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cjy23_bwm"/><path class="ex-8_4bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fox-20-bold" /></template>
