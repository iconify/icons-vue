<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onux0z-vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="onux0z-vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-20-bold" /></template>
