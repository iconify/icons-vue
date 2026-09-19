<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-4va7miy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y-4va7miy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:futbol-ball" /></template>
