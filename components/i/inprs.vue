<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d71j6bs8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21.065,"height":31.99,"left":0.005};
const content = `<path class="d71j6bs8z ingov-blue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:inprs" /></template>
