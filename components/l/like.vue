<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-3au3dcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="x-3au3dcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:like" /></template>
