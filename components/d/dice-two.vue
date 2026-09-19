<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb6y-xcsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vb6y-xcsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dice-two" /></template>
