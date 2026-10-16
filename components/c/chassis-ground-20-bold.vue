<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okw4g5bbu.css';
import '../../css/s/sbcow6bho.css';
import '../../css/l/l4c406ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="okw4g5bbu"/><path class="sbcow6bho"/><path class="l4c406ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chassis-ground-20-bold" /></template>
