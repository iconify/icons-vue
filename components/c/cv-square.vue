<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpvoz4dby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="lpvoz4dby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:cv-square" /></template>
