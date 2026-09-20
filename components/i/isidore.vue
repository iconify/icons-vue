<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf9l1q0nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kf9l1q0nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:isidore" /></template>
