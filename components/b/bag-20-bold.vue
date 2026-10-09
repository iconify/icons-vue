<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdy5yl5us.css';
import '../../css/k/kanbl39ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gdy5yl5us"/><path class="kanbl39ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bag-20-bold" /></template>
