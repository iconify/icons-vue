<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx9izvgqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kx9izvgqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:icons" /></template>
