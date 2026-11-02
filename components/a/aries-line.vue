<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7u_rtz6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7u_rtz6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aries-line" /></template>
