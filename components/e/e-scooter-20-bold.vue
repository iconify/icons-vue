<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m67zmkbra.css';
import '../../css/v/v2pxd9boo.css';
import '../../css/q/qj3hxybqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m67zmkbra"/><path class="v2pxd9boo"/><path class="qj3hxybqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-scooter-20-bold" /></template>
