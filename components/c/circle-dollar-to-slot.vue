<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_r80-udu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k_r80-udu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-dollar-to-slot" /></template>
