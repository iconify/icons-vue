<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inm7k4bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inm7k4bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:linkedin" /></template>
