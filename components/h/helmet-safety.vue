<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp0ly3b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="fp0ly3b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:helmet-safety" /></template>
