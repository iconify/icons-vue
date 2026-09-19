<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc2i8buif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tc2i8buif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:key" /></template>
