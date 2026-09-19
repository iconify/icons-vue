<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmz8a93qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zmz8a93qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dove" /></template>
