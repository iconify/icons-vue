<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfzq6nbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mfzq6nbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-board" /></template>
