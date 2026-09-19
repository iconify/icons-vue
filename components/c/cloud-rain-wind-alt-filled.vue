<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u60ek76zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u60ek76zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-rain-wind-alt-filled" /></template>
