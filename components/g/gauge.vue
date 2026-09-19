<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu8xy3b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qu8xy3b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:gauge" /></template>
