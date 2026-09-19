<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjjg7sbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hjjg7sbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:electric-light-bulb" /></template>
