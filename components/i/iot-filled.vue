<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7s8y0yps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k7s8y0yps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:iot-filled" /></template>
