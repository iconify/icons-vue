<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji9na9rtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ji9na9rtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:bookmark" /></template>
