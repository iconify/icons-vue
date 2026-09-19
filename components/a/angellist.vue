<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf7dcjbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tf7dcjbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:angellist" /></template>
