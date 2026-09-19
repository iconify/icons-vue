<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcwwrwb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rcwwrwb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-minus" /></template>
