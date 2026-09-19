<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7id7ozam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="o7id7ozam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:equals" /></template>
