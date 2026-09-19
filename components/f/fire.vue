<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9rrpac4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="m9rrpac4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:fire" /></template>
