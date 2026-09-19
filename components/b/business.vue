<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4e79wb0p.css';
import '../../css/m/myrkvvb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4e79wb0p"/><path class="myrkvvb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:business" /></template>
