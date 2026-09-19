<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0t5pub1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="w0t5pub1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-left" /></template>
