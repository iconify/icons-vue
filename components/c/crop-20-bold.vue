<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs8-z_yps.css';
import '../../css/e/ezgqvohnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gs8-z_yps"/><path class="ezgqvohnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crop-20-bold" /></template>
