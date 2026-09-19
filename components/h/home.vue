<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6vd-ibno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n6vd-ibno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:home" /></template>
