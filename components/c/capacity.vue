<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdt5ozjox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdt5ozjox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:capacity" /></template>
