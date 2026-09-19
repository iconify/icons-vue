<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5s6drg7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x5s6drg7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:fonticons" /></template>
