<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgyj5egpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wgyj5egpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:ads-square" /></template>
