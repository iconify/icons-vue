<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogkmfrk0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ogkmfrk0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrow-alt-circle-up" /></template>
