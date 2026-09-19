<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbwinxbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mbwinxbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hat-wizard" /></template>
