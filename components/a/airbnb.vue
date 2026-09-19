<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsre1t1xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zsre1t1xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:airbnb" /></template>
