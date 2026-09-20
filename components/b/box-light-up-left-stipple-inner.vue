<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_p8usboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="w_p8usboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-up-left-stipple-inner" /></template>
