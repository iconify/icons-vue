<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfgcicctr.css';
import '../../css/f/fu5dxhbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sfgcicctr"/><path class="fu5dxhbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-2-20-bold" /></template>
