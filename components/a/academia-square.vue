<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygl6n1i5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ygl6n1i5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:academia-square" /></template>
