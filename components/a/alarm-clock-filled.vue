<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3ochbcej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y3ochbcej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:alarm-clock-filled" /></template>
