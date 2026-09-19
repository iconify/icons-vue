<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbg85qbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fbg85qbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-middle-finger" /></template>
