<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uip1_obsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uip1_obsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lemon-squeezy-line" /></template>
