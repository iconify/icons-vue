<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckjs4eb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ckjs4eb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:africarxiv-square" /></template>
