<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki_1ns98y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki_1ns98y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fingerprint" /></template>
